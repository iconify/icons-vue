<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icj2v8t5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="icj2v8t5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:triangle-stroked-15" /></template>
