<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0d5-18fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b0d5-18fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:map" /></template>
