<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6pd55bue.css';
import '../../css/j/j7n6h9bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6pd55bue"/><path class="j7n6h9bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-arrow-down-enter-filled" /></template>
