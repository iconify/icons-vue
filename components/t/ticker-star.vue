<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la6-9sbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="la6-9sbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ticker-star" /></template>
