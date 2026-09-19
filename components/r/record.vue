<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjho78bvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="pjho78bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:record" /></template>
