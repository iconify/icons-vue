<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwh3sic_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwh3sic_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:message-x" /></template>
