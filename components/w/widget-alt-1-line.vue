<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iph2hoksm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iph2hoksm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:widget-alt-1-line" /></template>
