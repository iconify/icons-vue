<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb2gx18ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eb2gx18ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-wearing-backpack-walking-with-hiking-pole" /></template>
