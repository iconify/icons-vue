<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th04ddc4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th04ddc4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-times-bold" /></template>
