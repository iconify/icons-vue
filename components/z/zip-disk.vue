<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psyey8b0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psyey8b0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:zip-disk" /></template>
