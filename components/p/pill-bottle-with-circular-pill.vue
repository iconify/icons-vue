<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm4zygbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dm4zygbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pill-bottle-with-circular-pill" /></template>
