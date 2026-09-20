<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y93mowbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y93mowbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:scheduler-filled" /></template>
