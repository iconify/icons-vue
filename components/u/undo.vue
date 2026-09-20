<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg3urgmws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg3urgmws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:undo" /></template>
