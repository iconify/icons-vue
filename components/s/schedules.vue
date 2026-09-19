<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne82av_3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ne82av_3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:schedules" /></template>
