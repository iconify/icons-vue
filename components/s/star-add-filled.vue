<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xme1-zb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xme1-zb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:star-add-filled" /></template>
