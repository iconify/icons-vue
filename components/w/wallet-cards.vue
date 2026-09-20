<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjm_2bbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjm_2bbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wallet-cards" /></template>
