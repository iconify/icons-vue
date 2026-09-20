<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s285ntt_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nfc-off-outline" /></template>
<style>
.s285ntt_s {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.422L1.887 3.308l.713-.714l19.223 19.223l-.713.714L18.579 20zM8 16V9.421l-3-3v11.964q0 .23.192.423t.423.192H17.58l-3-3zm12 1.208l-1-1V5.616q0-.231-.192-.424T18.384 5H7.792l-1-1h11.593q.69 0 1.152.463T20 5.616zM9 15h4.579L9 10.421zm7-1.792l-1-1V9h-2.5v.708l-.971-.971q.09-.345.35-.54Q12.139 8 12.5 8H16zm-2.594-2.614");
}

</style>
