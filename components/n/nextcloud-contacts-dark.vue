<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv92jsiur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uv92jsiur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-contacts-dark" /></template>
