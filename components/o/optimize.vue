<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sq2d5abyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sq2d5abyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:optimize" /></template>
