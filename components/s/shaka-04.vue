<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6z-b0byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6z-b0byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shaka-04" /></template>
