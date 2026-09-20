<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an94cn0um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="an94cn0um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:wallet-fill" /></template>
