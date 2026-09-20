<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvh1t7b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvh1t7b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:vector-triangle-off" /></template>
