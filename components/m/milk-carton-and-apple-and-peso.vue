<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu4ps270m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mu4ps270m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:milk-carton-and-apple-and-peso" /></template>
