<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e32cefbaq.css';
import '../../css/o/os3k17bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="e32cefbaq"/><path class="os3k17bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="geo:ui-earth-west" /></template>
