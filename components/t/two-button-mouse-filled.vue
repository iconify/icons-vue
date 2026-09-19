<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pser2-bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="pser2-bxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:two-button-mouse-filled" /></template>
