<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9-8ignyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9-8ignyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:signpost4" /></template>
