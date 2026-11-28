<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvzn1-v5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvzn1-v5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:wallet-solid" /></template>
