<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t602nu8bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="t602nu8bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:stumbleupon" /></template>
