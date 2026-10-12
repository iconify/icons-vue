<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em2bklzzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="em2bklzzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:microchip-filled" /></template>
