<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w41a_vb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w41a_vb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-eye-off" /></template>
