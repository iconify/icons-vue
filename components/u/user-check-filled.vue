<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5h87bmtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="g5h87bmtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:user-check-filled" /></template>
