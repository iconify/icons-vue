<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5w-_6buy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b5w-_6buy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:safety" /></template>
