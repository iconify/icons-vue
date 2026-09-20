<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv2ni7q9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="dv2ni7q9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:x-solid" /></template>
