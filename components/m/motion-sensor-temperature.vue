<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_2q19p9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_2q19p9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:motion-sensor-temperature" /></template>
