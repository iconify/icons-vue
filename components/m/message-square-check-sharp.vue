<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq5hl4bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zq5hl4bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-check-sharp" /></template>
