<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6sjyt58t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t6sjyt58t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:receipt-indian-rupee-filled" /></template>
