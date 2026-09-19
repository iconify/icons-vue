<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ray6y6b4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ray6y6b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:moon" /></template>
