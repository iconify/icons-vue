<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9405_b9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d9405_b9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:open-envelope-right" /></template>
