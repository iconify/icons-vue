<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krs-b1nao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krs-b1nao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:percentage" /></template>
