<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc8alin5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qc8alin5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:octagon-pause-filled" /></template>
