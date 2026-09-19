<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-s9v8b6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":448};
const content = `<path class="k-s9v8b6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:steam" /></template>
