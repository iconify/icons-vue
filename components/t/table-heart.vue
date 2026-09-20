<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_-use06p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_-use06p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-heart" /></template>
