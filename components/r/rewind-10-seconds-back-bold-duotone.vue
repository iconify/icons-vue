<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ourjeh54g.css';
import '../../css/f/fgil9vbxo.css';
import '../../css/i/i7qoswbip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ourjeh54g"/><path clip-rule="evenodd" class="fgil9vbxo"/><path clip-rule="evenodd" class="i7qoswbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-10-seconds-back-bold-duotone" /></template>
