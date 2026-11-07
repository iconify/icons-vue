<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wahoyrbda.css';
import '../../css/p/pvm_5qbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wahoyrbda"/><path clip-rule="evenodd" class="pvm_5qbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-fall-minimalistic-bold" /></template>
