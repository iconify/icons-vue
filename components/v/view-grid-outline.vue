<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjzx0qo6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjzx0qo6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-grid-outline" /></template>
