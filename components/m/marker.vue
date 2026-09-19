<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xquo8mb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":961};
const content = `<path class="xquo8mb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:marker" /></template>
