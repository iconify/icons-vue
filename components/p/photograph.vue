<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igruemr1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="igruemr1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:photograph" /></template>
