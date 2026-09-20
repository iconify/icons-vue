<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvypesbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-sound-outline" /></template>
<style>
.lvypesbcy {
  fill: currentColor;
  d: path("M7 12.923V21V3zM7.616 22q-.672 0-1.144-.472T6 20.385V3.615q0-.67.472-1.143Q6.944 2 7.616 2h8.769q.67 0 1.143.472q.472.472.472 1.144v1.692h-1V3.616q0-.27-.173-.443T16.385 3h-8.77q-.269 0-.442.173T7 3.616v16.769q0 .269.173.442t.443.173h8.769q.269 0 .442-.173t.173-.442v-1.693h1v1.693q0 .67-.472 1.143q-.472.472-1.143.472zm4.972-15.912q.22-.22.22-.55q0-.329-.22-.549t-.55-.22t-.548.22t-.22.55t.22.549t.549.22t.549-.22m3.372 8.378l-.72-.72q.397-.333.646-.782t.249-.964t-.25-.964t-.645-.782l.72-.72q.536.48.855 1.111q.32.632.32 1.355t-.32 1.355q-.319.631-.856 1.11m2.143 2.143l-.708-.708q.775-.775 1.19-1.784Q19 13.106 19 12t-.416-2.116t-1.19-1.784l.708-.708q.921.916 1.41 2.108T20 12t-.488 2.5t-1.41 2.108");
}

</style>
