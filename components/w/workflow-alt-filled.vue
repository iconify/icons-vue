<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmde6-b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmde6-b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:workflow-alt-filled" /></template>
