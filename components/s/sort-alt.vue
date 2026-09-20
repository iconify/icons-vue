<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5q-mvb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="x5q-mvb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:sort-alt" /></template>
