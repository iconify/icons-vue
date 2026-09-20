<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qagtj4d3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="qagtj4d3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:user-pen" /></template>
