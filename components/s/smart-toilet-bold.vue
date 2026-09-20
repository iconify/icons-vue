<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy7fz0b3h.css';
import '../../css/s/snw44201m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy7fz0b3h"/><path class="snw44201m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:smart-toilet-bold" /></template>
