<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xysgi34gs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xysgi34gs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:roman-numeral-6" /></template>
