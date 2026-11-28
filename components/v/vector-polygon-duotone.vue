<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrssl0byk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary qrssl0byk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:vector-polygon-duotone" /></template>
