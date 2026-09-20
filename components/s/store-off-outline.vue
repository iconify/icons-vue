<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg0y7c3_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hg0y7c3_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:store-off-outline" /></template>
