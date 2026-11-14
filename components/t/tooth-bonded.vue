<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oysmyx4by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tooth-bonded" /></template>
<style>
.oysmyx4by {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.972 3.501q1.656-.744 3.494-.219q3.314.994 2.78 5.793q-.163 1.632-1.279 4.11q-.706 1.567-.991 2.505l-.994 4.473l-.004.019q-.33 1.318-1.728 1.318t-1.728-1.318l-1-4Q12.477 16 12 16t-.522.182l-1 4Q10.148 21.5 8.75 21.5t-1.728-1.318l-.004-.019l-.994-4.473q-.285-.938-.991-2.505q-1.116-2.478-1.278-4.102q-.535-4.807 2.789-5.804Q9.505 2.433 12 4.899q.683-.675 1.402-1.102q-.097.129-.133.285q-.036.157-.004.315q.858 4.291 6.156 4.849q.074.008.148.001q.073-.007.144-.028t.136-.055q.065-.035.123-.081q.057-.047.105-.103q.047-.057.082-.122t.057-.135t.03-.144q.015-.149-.027-.292t-.136-.259t-.225-.187t-.279-.087q-4.202-.442-4.844-3.651q-.013-.065-.037-.127t-.059-.118t-.078-.106t-.096-.091t-.111-.072t-.121-.052t-.129-.03t-.132-.006");
}

</style>
