<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlbqwq_cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlbqwq_cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:patreon-line" /></template>
