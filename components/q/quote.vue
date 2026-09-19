<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5u1et5dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="b5u1et5dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:quote" /></template>
