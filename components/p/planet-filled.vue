<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-_r8935p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-_r8935p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:planet-filled" /></template>
