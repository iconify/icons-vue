<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1swbq5zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z1swbq5zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:melpa" /></template>
