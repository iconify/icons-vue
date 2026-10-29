<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcnqqqv9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcnqqqv9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:water-balloon-solid" /></template>
