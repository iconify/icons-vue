<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-gel7b8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":1024};
const content = `<path class="p-gel7b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:wine" /></template>
