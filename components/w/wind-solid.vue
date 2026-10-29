<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmu5l1qta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmu5l1qta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wind-solid" /></template>
