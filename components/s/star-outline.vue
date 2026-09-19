<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynl0eabys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynl0eabys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:star-outline" /></template>
