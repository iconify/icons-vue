<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amxt-xpqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amxt-xpqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:utensils-crossed-filled" /></template>
