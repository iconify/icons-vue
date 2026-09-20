<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7a7_mvmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y7a7_mvmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:swamp" /></template>
