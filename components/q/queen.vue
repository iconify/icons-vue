<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjz6kxbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="rjz6kxbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:queen" /></template>
