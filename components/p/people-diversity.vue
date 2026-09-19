<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t89--hbtm.css';
import '../../css/s/sbh-k_brg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t89--hbtm"/><path class="sbh-k_brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:people-diversity" /></template>
