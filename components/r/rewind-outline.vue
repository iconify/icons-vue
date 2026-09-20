<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ioewjnb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ioewjnb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:rewind-outline" /></template>
