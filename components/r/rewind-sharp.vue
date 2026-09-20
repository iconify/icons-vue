<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq2_qrlix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq2_qrlix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rewind-sharp" /></template>
