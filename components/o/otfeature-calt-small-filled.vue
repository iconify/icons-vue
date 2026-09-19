<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1p9zxbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="d1p9zxbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-calt-small-filled" /></template>
