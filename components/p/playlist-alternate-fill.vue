<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igg6x_b9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igg6x_b9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:playlist-alternate-fill" /></template>
