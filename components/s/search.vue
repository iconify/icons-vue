<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5p08eobw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="a5p08eobw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:search" /></template>
