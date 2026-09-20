<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouera-xzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ouera-xzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:microsoftonedrive" /></template>
