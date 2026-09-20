<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfm657y6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rfm657y6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:watch-sharp-fill" /></template>
