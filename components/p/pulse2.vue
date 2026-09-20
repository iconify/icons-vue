<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-8ong1fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n-8ong1fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pulse2" /></template>
