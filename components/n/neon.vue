<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chai4np5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":470,"height":512};
const content = `<path class="chai4np5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:neon" /></template>
