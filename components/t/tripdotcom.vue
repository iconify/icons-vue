<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5gfub0go.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5gfub0go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tripdotcom" /></template>
