<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aedwb1bzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":35,"height":32};
const content = `<path class="aedwb1bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:telescope" /></template>
