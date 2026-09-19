<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tak0hzc8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tak0hzc8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:view-module" /></template>
