<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5q551bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5q551bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:pull-request-x" /></template>
