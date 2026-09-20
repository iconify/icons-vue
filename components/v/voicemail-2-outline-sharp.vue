<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-6g32bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:voicemail-2-outline-sharp" /></template>
<style>
.f-6g32bdt {
  fill: currentColor;
  d: path("M15.577 14.346q1 0 1.702-.682q.702-.683.702-1.664t-.702-1.673t-1.702-.692q-.98 0-1.683.692q-.702.692-.702 1.673q0 .39.124.724q.125.334.359.622h-3.35q.235-.288.359-.622q.124-.333.124-.724q0-.98-.702-1.673q-.702-.692-1.683-.692t-1.682.692T6.039 12t.702 1.664q.701.682 1.682.682zm-8.136-1.393Q7.04 12.56 7.04 12q0-.579.402-.972q.403-.393.982-.393t.992.393t.412.972t-.412.963t-.992.383t-.982-.393m7.154 0q-.403-.393-.403-.953q0-.579.403-.972t.982-.393t.991.393t.413.972t-.413.963t-.991.383t-.982-.393M3 19V5h18v14zm1-1h16V6H4zm0 0V6z");
}

</style>
