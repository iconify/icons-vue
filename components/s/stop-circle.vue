<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjdjl4z7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="zjdjl4z7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:stop-circle" /></template>
