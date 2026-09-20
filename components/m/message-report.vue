<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm2f1wbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm2f1wbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-report" /></template>
