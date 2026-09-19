<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyzz4-b2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyzz4-b2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wall-econic" /></template>
