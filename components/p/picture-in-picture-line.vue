<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_o_u3b0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_o_u3b0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:picture-in-picture-line" /></template>
