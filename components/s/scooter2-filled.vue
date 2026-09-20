<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj24h4blp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nj24h4blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:scooter2-filled" /></template>
