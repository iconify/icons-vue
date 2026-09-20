<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":285};
const content = `<path class="uinsy0slq"/><path class="dlsg5_oyz"/><path class="pwlwctdyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:pagekite" /></template>
<style>
.dlsg5_oyz {
  fill: var(--svg-color--b6b1b1, #b6b1b1);
  d: path("M22.837 187.856c3.068 27.315 6.069 58.652 9.577 96.507a2594 2594 0 0 1 88.56-43.423l-25.941-69.291z");
}

.pwlwctdyu {
  fill: var(--svg-color--748282, #748282);
  d: path("M13.422 114.016c2.152 15.307 4.524 33.606 7.085 55.417l85.945-20.253l30.88 84.2a2291 2291 0 0 1 50.227-22.289L141.076 86.93z");
}

.uinsy0slq {
  fill: var(--svg-color--e80022, #e80022);
  d: path("M206.052 203.265C237.813 190.014 256 183.436 256 183.436L189.698 0L0 40.15s4.022 11.406 10.833 56.141L152.495 64.46z");
}

</style>
