<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak0ww7bmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ak0ww7bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:sidebar-simple-close-light" /></template>
