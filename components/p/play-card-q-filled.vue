<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la6i2f31y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la6i2f31y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:play-card-q-filled" /></template>
