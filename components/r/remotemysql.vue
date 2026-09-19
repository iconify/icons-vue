<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gner02b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gner02b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:remotemysql" /></template>
