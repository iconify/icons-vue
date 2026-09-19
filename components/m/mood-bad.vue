<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6q-f6bnh.css';
import '../../css/z/z7n81bcbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r6q-f6bnh"/><path class="z7n81bcbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:mood-bad" /></template>
