<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn48e2bxu.css';
import '../../css/q/qe1l0xb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn48e2bxu"/><path class="qe1l0xb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:muted-outline" /></template>
