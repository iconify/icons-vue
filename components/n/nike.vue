<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjk26-b5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjk26-b5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:nike" /></template>
