<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzi2ayb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xzi2ayb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ticket-minus-filled" /></template>
