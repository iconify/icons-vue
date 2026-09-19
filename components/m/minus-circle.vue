<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upv2lacpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="upv2lacpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:minus-circle" /></template>
