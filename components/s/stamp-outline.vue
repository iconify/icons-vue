<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htane7bpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="htane7bpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:stamp-outline" /></template>
