<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/red0k8iug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="red0k8iug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:moon-fill-12" /></template>
