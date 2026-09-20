<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfkqb6b5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cfkqb6b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wide-rounded-rectangle-outline" /></template>
