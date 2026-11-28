<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8qpqobef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8qpqobef primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:vector-corner-duotone" /></template>
