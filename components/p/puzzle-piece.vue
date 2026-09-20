<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykrathbtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykrathbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:puzzle-piece" /></template>
