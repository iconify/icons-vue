<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szwhrib-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="szwhrib-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tududi-light" /></template>
