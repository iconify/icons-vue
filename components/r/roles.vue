<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pal8a7bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="pal8a7bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:roles" /></template>
