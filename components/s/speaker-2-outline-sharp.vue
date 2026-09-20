<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgtphacri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speaker-2-outline-sharp" /></template>
<style>
.wgtphacri {
  fill: currentColor;
  d: path("M7 17.366h10V4H7zm5-4.962q1.362 0 2.306-.935q.944-.934.944-2.296t-.944-2.315q-.944-.954-2.306-.954t-2.306.954t-.944 2.315t.944 2.296t2.306.935m0-1q-.928 0-1.589-.655t-.661-1.58t.661-1.586T12 6.923t1.589.66t.661 1.585t-.661 1.581t-1.589.655m0 4.154q.29 0 .51-.21t.22-.521q0-.29-.22-.51t-.52-.22t-.51.22t-.21.52t.21.51t.52.21M15.654 21H8.327v-1h.923q.748 0 1.33-.458t.799-1.177H6V3h12v15.366h-5.379q.218.719.794 1.176T14.75 20h.904zM12 9.173");
}

</style>
