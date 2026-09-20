<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttr3kfbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttr3kfbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:udio" /></template>
