<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa-nw0wun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa-nw0wun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-return-outline" /></template>
