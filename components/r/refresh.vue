<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox92i9e_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ox92i9e_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:refresh" /></template>
