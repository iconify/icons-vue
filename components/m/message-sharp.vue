<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa1b8rrtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa1b8rrtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-sharp" /></template>
