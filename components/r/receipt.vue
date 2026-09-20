<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okv6f5bis.css';
import '../../css/u/uq6a4ac5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="okv6f5bis"/><path class="uq6a4ac5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:receipt" /></template>
