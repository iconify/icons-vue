<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_utrmb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_utrmb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:overscan" /></template>
