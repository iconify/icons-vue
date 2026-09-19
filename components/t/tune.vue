<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izqhqn6_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="izqhqn6_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:tune" /></template>
