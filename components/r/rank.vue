<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqkdahb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gqkdahb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:rank" /></template>
