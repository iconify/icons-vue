<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra22vqljm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ra22vqljm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:rectangle-ellipsis-filled" /></template>
