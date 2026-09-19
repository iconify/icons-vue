<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s750qgbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s750qgbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:vimeo" /></template>
