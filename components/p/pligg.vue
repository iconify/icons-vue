<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjznslb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="zjznslb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pligg" /></template>
