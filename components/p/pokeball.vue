<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9i5wjlxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="d9i5wjlxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:pokeball" /></template>
