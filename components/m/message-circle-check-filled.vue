<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdrs85b3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tdrs85b3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-circle-check-filled" /></template>
