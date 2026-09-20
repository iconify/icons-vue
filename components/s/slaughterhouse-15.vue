<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvmdrtmdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dvmdrtmdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:slaughterhouse-15" /></template>
