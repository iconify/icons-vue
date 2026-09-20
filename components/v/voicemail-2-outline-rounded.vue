<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofiendb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:voicemail-2-outline-rounded" /></template>
<style>
.ofiendb4d {
  fill: currentColor;
  d: path("M15.577 14.346q1 0 1.702-.682q.702-.683.702-1.664t-.702-1.673t-1.702-.692q-.98 0-1.683.692q-.702.692-.702 1.673q0 .39.124.724q.125.334.359.622h-3.35q.235-.288.359-.622q.124-.333.124-.724q0-.98-.702-1.673q-.702-.692-1.683-.692t-1.682.692T6.039 12t.702 1.664q.701.682 1.682.682zm-8.136-1.393Q7.04 12.56 7.04 12q0-.579.402-.972q.403-.393.982-.393t.992.393t.412.972t-.412.963t-.992.383t-.982-.393m7.154 0q-.403-.393-.403-.953q0-.579.403-.972t.982-.393t.991.393t.413.972t-.413.963t-.991.383t-.982-.393M4.615 19q-.69 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm0-1h14.77q.23 0 .423-.192t.192-.424V6.616q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616v10.769q0 .23.192.423t.423.192M4 18V6z");
}

</style>
