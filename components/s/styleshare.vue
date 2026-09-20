<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh-wf7b8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh-wf7b8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:styleshare" /></template>
