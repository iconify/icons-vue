<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck53eebmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ck53eebmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rallly" /></template>
