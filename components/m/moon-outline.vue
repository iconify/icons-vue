<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiwh17hkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="aiwh17hkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:moon-outline" /></template>
