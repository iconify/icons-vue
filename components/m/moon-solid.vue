<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tibruob8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tibruob8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:moon-solid" /></template>
