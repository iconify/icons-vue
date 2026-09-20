<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh2gx_b5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eh2gx_b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:minus-circle-outline" /></template>
