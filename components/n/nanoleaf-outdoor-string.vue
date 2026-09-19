<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he5lwbciq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="he5lwbciq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:nanoleaf-outdoor-string" /></template>
