<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-a68sb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g-a68sb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-walking-with-hiking-pole" /></template>
