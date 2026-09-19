<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faxo8wb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="faxo8wb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:trash-x-filled" /></template>
