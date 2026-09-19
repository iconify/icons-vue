<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf8h10baa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nf8h10baa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:pause-solid" /></template>
