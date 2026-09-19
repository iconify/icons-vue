<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jeg19xb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jeg19xb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-minus-light" /></template>
