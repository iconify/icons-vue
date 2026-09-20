<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v57lhh3cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-screensaver-sharp" /></template>
<style>
.v57lhh3cp {
  fill: currentColor;
  d: path("M6 22V2h12.077v4.83H19v3.686h-.923V22zm2.5-7.23h7.077l-2.144-2.886l-1.894 2.5l-1.395-1.844zm6.857-4.838q.22-.221.22-.549t-.221-.547t-.55-.22t-.547.221t-.22.549t.221.548t.549.22t.548-.222");
}

</style>
