<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o07e7hgim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o07e7hgim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:stop-outline" /></template>
