<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t04ot3bgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t04ot3bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:triangle" /></template>
