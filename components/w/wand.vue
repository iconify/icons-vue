<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py46mcb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":472};
const content = `<path class="py46mcb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:wand" /></template>
