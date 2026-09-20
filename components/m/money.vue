<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrrnxvlop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrrnxvlop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:money" /></template>
