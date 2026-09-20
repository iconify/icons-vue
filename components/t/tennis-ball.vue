<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx63-zb5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx63-zb5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tennis-ball" /></template>
