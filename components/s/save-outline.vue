<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5fwnfbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e5fwnfbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:save-outline" /></template>
