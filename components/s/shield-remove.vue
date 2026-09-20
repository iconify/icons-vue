<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_35ezbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_35ezbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-remove" /></template>
