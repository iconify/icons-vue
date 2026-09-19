<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfy829k1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfy829k1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tesla-trunk" /></template>
