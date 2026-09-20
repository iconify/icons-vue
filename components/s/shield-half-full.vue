<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtc8-gbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtc8-gbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-half-full" /></template>
