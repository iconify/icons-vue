<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr7o58bcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr7o58bcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:tv-solid" /></template>
