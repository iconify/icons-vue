<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-j6hab_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="d-j6hab_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:officechair" /></template>
