<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln9qkabwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="ln9qkabwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:natural-11" /></template>
