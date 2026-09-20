<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsr72_20l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vsr72_20l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:split" /></template>
