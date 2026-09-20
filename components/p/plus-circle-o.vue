<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg-yorbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sg-yorbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:plus-circle-o" /></template>
