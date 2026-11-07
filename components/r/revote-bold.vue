<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddmmyzkas.css';
import '../../css/l/lz0rx605g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ddmmyzkas"/><path class="lz0rx605g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:revote-bold" /></template>
