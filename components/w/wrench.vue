<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1np-_ozh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="x1np-_ozh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:wrench" /></template>
