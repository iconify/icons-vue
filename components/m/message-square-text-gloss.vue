<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl8iuabrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl8iuabrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-square-text-gloss" /></template>
