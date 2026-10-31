<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0jnlgbfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0jnlgbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:menu-alt-5-duotone-round" /></template>
