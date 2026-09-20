<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tare22g5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tare22g5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:menu-2-filled" /></template>
