<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etu2wfuwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etu2wfuwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tvnz" /></template>
