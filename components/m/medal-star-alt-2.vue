<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xahhmbe9e.css';
import '../../css/l/l86i2yr1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xahhmbe9e"/><path class="l86i2yr1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:medal-star-alt-2" /></template>
