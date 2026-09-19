<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b48lj4b-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1792};
const content = `<path class="b48lj4b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:object-group" /></template>
