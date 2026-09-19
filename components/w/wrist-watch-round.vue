<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahpckbcel.css';
import '../../css/e/e-5v66b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahpckbcel"/><path class="e-5v66b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wrist-watch-round" /></template>
