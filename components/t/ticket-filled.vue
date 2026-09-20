<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqqwndb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="pqqwndb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:ticket-filled" /></template>
