<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2n529b7c.css';
import '../../css/d/d363y7bqh.css';
import '../../css/g/gtfd-mlws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j2n529b7c"/><path class="d363y7bqh"/><path class="gtfd-mlws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wineglass-bold-duotone" /></template>
