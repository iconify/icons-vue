<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3r9m9bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b3r9m9bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:toilet" /></template>
