<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuwky7bde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cuwky7bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:piggy-bank-filled" /></template>
