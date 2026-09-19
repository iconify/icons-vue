<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn2oh2b2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qn2oh2b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:message-dots-solid" /></template>
