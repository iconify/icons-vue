<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb6ciacld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bb6ciacld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wrap-right-fill-20" /></template>
