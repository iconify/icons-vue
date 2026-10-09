<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lae2_dgov.css';
import '../../css/z/znm6bw41g.css';
import '../../css/i/iiq2hgbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lae2_dgov"/><path class="znm6bw41g"/><path class="iiq2hgbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:price-up-20" /></template>
