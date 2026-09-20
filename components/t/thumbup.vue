<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0w7ilbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="g0w7ilbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:thumbup" /></template>
