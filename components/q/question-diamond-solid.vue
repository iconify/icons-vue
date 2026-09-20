<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzf7ggg9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzf7ggg9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:question-diamond-solid" /></template>
