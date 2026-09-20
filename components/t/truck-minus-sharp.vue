<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6a7f-bca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6a7f-bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:truck-minus-sharp" /></template>
