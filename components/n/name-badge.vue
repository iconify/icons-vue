<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygbngee6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ygbngee6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:name-badge" /></template>
