<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik7de50zm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik7de50zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:newpipe" /></template>
