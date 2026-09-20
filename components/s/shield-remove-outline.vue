<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr0ysc8zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr0ysc8zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shield-remove-outline" /></template>
