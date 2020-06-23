            <van-popup :show="showGoOnTimePicker"  position="bottom">
                <van-datetime-picker type="time" value="6:00"
                                     @cancel="onCancelDatePicker"
                                     @confirm="onConfirmGoOnTimePicker"
                                     :formatter="formatter"
                />
            </van-popup>
