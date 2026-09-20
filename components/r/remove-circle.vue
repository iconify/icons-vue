<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir8a84vmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ir8a84vmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:remove-circle" /></template>
