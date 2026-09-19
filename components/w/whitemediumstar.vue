<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6nv3mz1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s6nv3mz1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:whitemediumstar" /></template>
