<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eis0ofcwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="eis0ofcwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:shopping-bag" /></template>
