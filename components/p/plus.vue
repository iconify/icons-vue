<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6tvq3b9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a6tvq3b9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:plus" /></template>
