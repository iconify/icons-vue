<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8oe4bcvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o8oe4bcvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opensuse-evergreen-light" /></template>
