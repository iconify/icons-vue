<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nru_erb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nru_erb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-padding-bottom-filled" /></template>
