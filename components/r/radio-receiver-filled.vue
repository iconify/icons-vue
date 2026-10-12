<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqx-81tcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rqx-81tcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:radio-receiver-filled" /></template>
