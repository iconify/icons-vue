<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opq8e0bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="opq8e0bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:rack-ipc-question" /></template>
