<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxrkksz8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxrkksz8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:skip-plus" /></template>
