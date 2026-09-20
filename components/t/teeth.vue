<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt3etyhii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rt3etyhii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:teeth" /></template>
