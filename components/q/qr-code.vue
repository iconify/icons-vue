<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3crd64rj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3crd64rj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:qr-code" /></template>
