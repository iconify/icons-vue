<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hisc6g5br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hisc6g5br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:wine-solid" /></template>
