<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th_w9mbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th_w9mbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:toilet-paper-off" /></template>
