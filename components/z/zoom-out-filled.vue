<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3i6zbk6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h3i6zbk6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:zoom-out-filled" /></template>
