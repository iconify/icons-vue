<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3hy0rjyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p3hy0rjyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:user-reading-reading" /></template>
