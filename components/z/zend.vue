<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe8i44bza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe8i44bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:zend" /></template>
