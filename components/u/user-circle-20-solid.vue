<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2hq26fol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m2hq26fol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:user-circle-20-solid" /></template>
