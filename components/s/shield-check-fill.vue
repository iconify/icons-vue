<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xev9dlyyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xev9dlyyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-check-fill" /></template>
