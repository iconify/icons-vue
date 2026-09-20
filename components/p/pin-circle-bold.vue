<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwcuezj6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dwcuezj6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pin-circle-bold" /></template>
