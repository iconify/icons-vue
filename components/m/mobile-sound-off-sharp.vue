<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep9vkevnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-sound-off-sharp" /></template>
<style>
.ep9vkevnu {
  fill: currentColor;
  d: path("m16.816 13.414l-.781-.776q.05-.15.075-.31q.025-.159.025-.328q0-.516-.25-.964t-.645-.782l.72-.72q.536.48.855 1.111q.32.632.32 1.355q0 .358-.08.72t-.24.694m2.148 2.123l-.732-.733q.384-.637.577-1.34T19 12q0-1.106-.416-2.116q-.415-1.009-1.19-1.784l.708-.708q.921.916 1.41 2.108T20 12q0 .967-.265 1.86q-.266.894-.771 1.677m1.882 6.667L1.392 2.75l.708-.708l19.454 19.454zM12.588 6.087q.22-.22.22-.549t-.22-.549t-.55-.22t-.548.22t-.22.55t.22.548t.549.22t.549-.22M6 22V5.942l12 12V22zm6.692-12.234L6.03 3.14V2H18v2.458z");
}

</style>
