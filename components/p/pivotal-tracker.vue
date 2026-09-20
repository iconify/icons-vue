<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_25ckb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_25ckb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pivotal-tracker" /></template>
