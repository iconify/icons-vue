<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udestw15j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="udestw15j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:razer-light" /></template>
