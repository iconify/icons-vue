<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehso6ts7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ehso6ts7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wallet-cards-sharp-fill" /></template>
