<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yde9zneln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yde9zneln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:server-fill" /></template>
