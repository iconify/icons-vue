<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltgqwf-9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltgqwf-9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:unreal" /></template>
