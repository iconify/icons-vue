<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x63qx2bsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x63qx2bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:neos" /></template>
