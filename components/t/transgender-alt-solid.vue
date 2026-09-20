<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjgs9xbck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mjgs9xbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:transgender-alt-solid" /></template>
