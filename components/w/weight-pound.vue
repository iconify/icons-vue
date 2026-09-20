<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v94pcac6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v94pcac6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:weight-pound" /></template>
