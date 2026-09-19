<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxpyd0bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxpyd0bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:toast" /></template>
