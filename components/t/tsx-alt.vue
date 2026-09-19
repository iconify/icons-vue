<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8al6yiie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o8al6yiie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:tsx-alt" /></template>
