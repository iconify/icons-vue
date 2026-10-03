<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykoimm3yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ykoimm3yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pydantic-logfire-light" /></template>
