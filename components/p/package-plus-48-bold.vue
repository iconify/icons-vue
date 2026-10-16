<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6_n-55ky.css';
import '../../css/r/r4-rvcapq.css';
import '../../css/g/ggak2qltj.css';
import '../../css/j/jyfi0eawb.css';
import '../../css/w/wii29dbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p6_n-55ky"/><path class="r4-rvcapq"/><path class="ggak2qltj"/><path class="jyfi0eawb"/><path class="wii29dbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:package-plus-48-bold" /></template>
