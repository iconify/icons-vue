<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygu0xdb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ygu0xdb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:msgvault-dark" /></template>
