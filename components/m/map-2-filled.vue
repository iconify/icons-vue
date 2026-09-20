<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_oty8pjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_oty8pjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:map-2-filled" /></template>
