<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db18-0-vh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="db18-0-vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:red-apple-small" /></template>
