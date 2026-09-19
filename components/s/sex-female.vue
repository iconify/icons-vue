<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pscnzhg3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1664};
const content = `<path class="pscnzhg3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:sex-female" /></template>
