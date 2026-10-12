<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyikwltxa.css';
import '../../css/v/vfl-qubxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyikwltxa"/><path class="vfl-qubxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:monitor-smartphone-filled" /></template>
