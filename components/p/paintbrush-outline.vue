<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5r6won4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k5r6won4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:paintbrush-outline" /></template>
