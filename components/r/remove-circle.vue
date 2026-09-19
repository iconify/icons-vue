<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1_emcbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="p1_emcbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:remove-circle" /></template>
