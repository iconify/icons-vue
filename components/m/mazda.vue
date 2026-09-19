<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0ad9xbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0ad9xbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:mazda" /></template>
