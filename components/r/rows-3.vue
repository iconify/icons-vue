<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvx0nbcqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvx0nbcqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:rows-3" /></template>
