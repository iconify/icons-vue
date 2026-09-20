<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkg_txz7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkg_txz7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:robot-happy-fill" /></template>
