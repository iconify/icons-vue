<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf4murbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lf4murbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:wallet-filled" /></template>
