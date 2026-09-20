<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu2s_jbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu2s_jbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:timer-2-fill" /></template>
