<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbbc3-_rw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lbbc3-_rw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:underline-square-solid" /></template>
