<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b45tcn2fu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b45tcn2fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:microsoft-windows" /></template>
