<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3ju9cb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3ju9cb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-strength-1-alert" /></template>
