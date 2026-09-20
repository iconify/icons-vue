<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6zc0dp-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a6zc0dp-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:surprise" /></template>
