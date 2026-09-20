<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4r1u1cta.css';
import '../../css/k/kmh9fqkcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t4r1u1cta"/><path class="kmh9fqkcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:qtum" /></template>
