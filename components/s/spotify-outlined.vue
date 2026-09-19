<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk5wt0bov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pk5wt0bov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:spotify-outlined" /></template>
