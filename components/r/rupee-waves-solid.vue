<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc1hzub-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc1hzub-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:rupee-waves-solid" /></template>
