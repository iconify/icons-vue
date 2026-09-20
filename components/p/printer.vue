<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqvmb8bcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mqvmb8bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:printer" /></template>
