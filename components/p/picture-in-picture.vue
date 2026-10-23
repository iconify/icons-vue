<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj-6jvb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lj-6jvb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:picture-in-picture" /></template>
