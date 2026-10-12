<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moluqpgom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="moluqpgom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:pin-off-filled" /></template>
