<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i168pb04v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="i168pb04v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:rules" /></template>
