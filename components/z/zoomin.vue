<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wirxgc2mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wirxgc2mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:zoomin" /></template>
