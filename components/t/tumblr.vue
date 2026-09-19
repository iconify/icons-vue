<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjxr8sbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="kjxr8sbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:tumblr" /></template>
