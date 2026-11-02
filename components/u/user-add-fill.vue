<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkhs_xi9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkhs_xi9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-add-fill" /></template>
