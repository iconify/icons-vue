<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q01kas6kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="q01kas6kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:world-solid" /></template>
