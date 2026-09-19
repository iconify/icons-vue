<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa3hvldyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":456,"height":512};
const content = `<path class="xa3hvldyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:reasonstudios" /></template>
