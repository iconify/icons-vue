<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4tjj3_pn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4tjj3_pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:store-check" /></template>
