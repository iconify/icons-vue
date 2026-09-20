<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0zpqxnly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u0zpqxnly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wallet-cards-fill" /></template>
