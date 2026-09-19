<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j286beboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":417,"height":512};
const content = `<path class="j286beboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:yorick" /></template>
