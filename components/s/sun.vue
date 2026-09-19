<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5euglb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="b5euglb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:sun" /></template>
