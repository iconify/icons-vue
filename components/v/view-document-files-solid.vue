<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kl1h7tboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kl1h7tboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:view-document-files-solid" /></template>
