<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khoq0k05p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khoq0k05p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:playstation-3" /></template>
