<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nif2_eh7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nif2_eh7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:virus-slash" /></template>
