<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y93_u216t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="y93_u216t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:punch-out" /></template>
