<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhx0ppbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sim-card-lock-sharp" /></template>
<style>
.hhx0ppbbx {
  fill: currentColor;
  d: path("M9.116 15.77h5.769V11h-1V9.885q0-.778-.55-1.332Q12.787 8 12 8t-1.336.554t-.548 1.33V11h-1zM10.885 11V9.892q0-.47.326-.797T12 8.77t.79.326t.326.797V11zM5 21V8.423L10.423 3H19v18z");
}

</style>
