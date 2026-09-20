<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvgy__y-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvgy__y-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:minus-waves-solid" /></template>
