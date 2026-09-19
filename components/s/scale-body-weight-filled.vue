<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww20d8b1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ww20d8b1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:scale-body-weight-filled" /></template>
