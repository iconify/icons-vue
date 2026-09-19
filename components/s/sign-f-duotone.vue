<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4is_sbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4is_sbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sign-f-duotone" /></template>
