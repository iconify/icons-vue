<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kof_8-b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="kof_8-b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:more" /></template>
