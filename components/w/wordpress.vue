<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic942e1qd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ic942e1qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:wordpress" /></template>
