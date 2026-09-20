<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aykwv9b4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="aykwv9b4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:send-outline" /></template>
