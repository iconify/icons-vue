<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv8tocczk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-sound-outline-sharp" /></template>
<style>
.iv8tocczk {
  fill: currentColor;
  d: path("M7 12.923V21V3zM6 22V2h12v3.308h-1V3H7v18h10v-2.308h1V22zm6.588-15.913q.22-.22.22-.549t-.22-.549t-.55-.22t-.548.22t-.22.55t.22.548t.549.22t.549-.22m3.372 8.378l-.72-.719q.397-.333.646-.782t.249-.964t-.25-.965t-.645-.781l.72-.72q.536.48.855 1.111q.32.632.32 1.355t-.32 1.355q-.319.631-.856 1.11m2.143 2.143l-.708-.708q.775-.775 1.19-1.784Q19 13.106 19 12t-.416-2.116t-1.19-1.784l.708-.708q.921.916 1.41 2.108T20 12t-.488 2.5t-1.41 2.108");
}

</style>
