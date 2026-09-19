<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki8ur8pfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ki8ur8pfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:minus-circle" /></template>
