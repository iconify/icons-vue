<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba8wc7b-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba8wc7b-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-warning" /></template>
