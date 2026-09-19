<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfh3h2bbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bfh3h2bbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:store" /></template>
