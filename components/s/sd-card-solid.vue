<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7vn98a0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="w7vn98a0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:sd-card-solid" /></template>
