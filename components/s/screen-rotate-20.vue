<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5r654krd.css';
import '../../css/r/rzv19ackg.css';
import '../../css/k/kiwq7bbdz.css';
import '../../css/l/lo37u5bfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f5r654krd"/><path class="rzv19ackg"/><path class="kiwq7bbdz"/><path class="lo37u5bfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:screen-rotate-20" /></template>
