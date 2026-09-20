<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x68s73jbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="x68s73jbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:success-multiple-filled" /></template>
