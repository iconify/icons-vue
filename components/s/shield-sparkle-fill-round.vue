<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe9nqr8no.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pe9nqr8no"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-sparkle-fill-round" /></template>
