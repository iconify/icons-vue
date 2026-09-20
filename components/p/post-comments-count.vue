<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6j2iob0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="p6j2iob0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:post-comments-count" /></template>
