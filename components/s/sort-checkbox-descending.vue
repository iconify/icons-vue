<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t93jw3bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t93jw3bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-checkbox-descending" /></template>
