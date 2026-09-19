<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0ui89byk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":384};
const content = `<path class="z0ui89byk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:play-for-work" /></template>
