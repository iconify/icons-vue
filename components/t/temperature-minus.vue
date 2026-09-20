<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bahqo5bjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bahqo5bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:temperature-minus" /></template>
