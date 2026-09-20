<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7q_wsbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w7q_wsbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shield-2-solid" /></template>
