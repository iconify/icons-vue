<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cknmu4bsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cknmu4bsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:venus" /></template>
