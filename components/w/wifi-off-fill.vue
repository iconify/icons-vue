<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5b48-b9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5b48-b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wifi-off-fill" /></template>
