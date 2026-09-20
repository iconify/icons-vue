<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcht8racb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="jcht8racb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:user-lock-filled" /></template>
