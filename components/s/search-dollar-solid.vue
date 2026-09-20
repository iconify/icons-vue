<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak5-9jb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ak5-9jb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:search-dollar-solid" /></template>
