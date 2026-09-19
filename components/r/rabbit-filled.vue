<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd6y7dbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pd6y7dbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:rabbit-filled" /></template>
