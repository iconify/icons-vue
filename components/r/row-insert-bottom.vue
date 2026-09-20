<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zko6-tb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zko6-tb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:row-insert-bottom" /></template>
