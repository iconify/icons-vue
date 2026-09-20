<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg0y5xmtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg0y5xmtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:unlocked-minus-outline" /></template>
