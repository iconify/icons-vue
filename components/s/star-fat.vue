<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w35xc6b7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path clip-rule="evenodd" class="w35xc6b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:star-fat" /></template>
