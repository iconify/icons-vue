<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz9olu_-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":508,"height":512};
const content = `<path class="dz9olu_-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:silverstripe" /></template>
