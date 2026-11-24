<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbltlh2de.css';
import '../../css/f/f0xl0fb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qbltlh2de"/><path class="f0xl0fb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:save-off-filled" /></template>
