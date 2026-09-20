<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0oa4jz6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path clip-rule="evenodd" class="i0oa4jz6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:raycast" /></template>
