<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqj4sr0ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pqj4sr0ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:question" /></template>
