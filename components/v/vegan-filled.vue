<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejb-d7dxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ejb-d7dxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:vegan-filled" /></template>
