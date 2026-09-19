<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imwvrfm9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="imwvrfm9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pagesetup" /></template>
