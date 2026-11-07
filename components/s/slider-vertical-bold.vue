<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yq81qobph.css';
import '../../css/c/cp8pj3bmi.css';
import '../../css/z/zv5zc6bto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq81qobph"/><path class="cp8pj3bmi"/><path class="zv5zc6bto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:slider-vertical-bold" /></template>
