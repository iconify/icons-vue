<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykxdrx_sp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ykxdrx_sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:zoom-out-filled" /></template>
