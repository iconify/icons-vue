<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efns2sepq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efns2sepq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:umage-carmina" /></template>
