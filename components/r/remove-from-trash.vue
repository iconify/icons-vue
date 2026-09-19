<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_lx8hlse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="c_lx8hlse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:remove-from-trash" /></template>
