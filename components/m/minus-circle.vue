<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huf-eeblg.css';
import '../../css/a/arr-9f6dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="huf-eeblg"/><path class="arr-9f6dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:minus-circle" /></template>
