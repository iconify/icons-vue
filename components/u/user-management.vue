<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu8c7vezn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yu8c7vezn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:user-management" /></template>
