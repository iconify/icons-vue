<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz9eh_b1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qz9eh_b1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:user-minus" /></template>
