<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6v207bvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u6v207bvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user" /></template>
