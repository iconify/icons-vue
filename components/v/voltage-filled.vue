<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubk51wbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ubk51wbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:voltage-filled" /></template>
