<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_e1699uz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="c_e1699uz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:shield-check" /></template>
