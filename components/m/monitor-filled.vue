<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amohcgtzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amohcgtzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:monitor-filled" /></template>
