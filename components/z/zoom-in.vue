<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuch1achf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xuch1achf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:zoom-in" /></template>
