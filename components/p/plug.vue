<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpwcj4boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpwcj4boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:plug" /></template>
