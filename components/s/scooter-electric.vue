<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl5p9ubwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl5p9ubwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:scooter-electric" /></template>
