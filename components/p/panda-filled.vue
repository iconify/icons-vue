<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbw_iwb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vbw_iwb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:panda-filled" /></template>
