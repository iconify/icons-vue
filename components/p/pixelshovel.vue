<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-f8v1txm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f-f8v1txm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pixelshovel" /></template>
