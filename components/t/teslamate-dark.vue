<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm0wiogcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cm0wiogcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:teslamate-dark" /></template>
