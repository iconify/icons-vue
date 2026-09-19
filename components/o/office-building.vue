<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6n2v-bef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="b6n2v-bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:office-building" /></template>
