<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfi618g_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="mfi618g_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squaret" /></template>
