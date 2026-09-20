<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqy5s6rdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqy5s6rdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:pin-small" /></template>
