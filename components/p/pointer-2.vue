<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9p2uebrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9p2uebrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pointer-2" /></template>
