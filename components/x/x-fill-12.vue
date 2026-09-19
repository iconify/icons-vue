<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmf27ubaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="bmf27ubaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:x-fill-12" /></template>
