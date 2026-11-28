<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhj9y3icm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhj9y3icm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shopping-bag-solid" /></template>
