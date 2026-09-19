<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxs1z5b8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="yxs1z5b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:rxjs" /></template>
