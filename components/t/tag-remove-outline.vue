<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to542-bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to542-bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-remove-outline" /></template>
