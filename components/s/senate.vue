<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it17_8b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it17_8b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:senate" /></template>
