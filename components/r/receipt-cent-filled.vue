<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqj1_qbxe.css';
import '../../css/q/qcjhzlq8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqj1_qbxe"/><path clip-rule="evenodd" class="qcjhzlq8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:receipt-cent-filled" /></template>
