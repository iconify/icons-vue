<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlbtvwxcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qlbtvwxcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:origamivault-light" /></template>
