<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt6plcbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":832,"height":1024};
const content = `<path class="bt6plcbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:punisher" /></template>
