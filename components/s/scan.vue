<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfbgv4bbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfbgv4bbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:scan" /></template>
