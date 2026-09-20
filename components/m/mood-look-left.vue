<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfba-8anb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfba-8anb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:mood-look-left" /></template>
