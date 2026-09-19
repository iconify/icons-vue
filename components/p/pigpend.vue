<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ej-1i0yet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ej-1i0yet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pigpend" /></template>
