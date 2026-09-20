<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba9x64_qo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba9x64_qo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:user" /></template>
