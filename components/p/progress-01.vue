<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_c5_kbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="a_c5_kbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:progress-01" /></template>
