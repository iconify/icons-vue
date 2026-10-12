<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yneuenbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yneuenbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:phone-off-filled" /></template>
