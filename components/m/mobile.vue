<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhls-y5sy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1472,"height":1600};
const content = `<path class="bhls-y5sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:mobile" /></template>
