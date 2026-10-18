<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b16z4ezve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b16z4ezve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:thumbs-down" /></template>
