<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7fmnlb4r.css';
import '../../css/g/g5pb60rja.css';
import '../../css/u/u7db4chhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="g5pb60rja"/><path class="u7db4chhd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:office-building-tall-2" /></template>
