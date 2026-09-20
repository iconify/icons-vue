<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh1ztlbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="vh1ztlbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:trend-up-solid" /></template>
