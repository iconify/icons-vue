<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs65zonnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="gs65zonnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:puzzle" /></template>
