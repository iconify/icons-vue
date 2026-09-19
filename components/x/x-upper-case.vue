<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3dv7sbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":769,"height":1024};
const content = `<path class="r3dv7sbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:x-upper-case" /></template>
