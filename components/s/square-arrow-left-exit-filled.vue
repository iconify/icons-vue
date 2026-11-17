<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tua-0ebsr.css';
import '../../css/h/h7kltebkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tua-0ebsr"/><path class="h7kltebkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-arrow-left-exit-filled" /></template>
