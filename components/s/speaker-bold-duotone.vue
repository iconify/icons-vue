<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke4nxkbkt.css';
import '../../css/s/sfqi7kbmf.css';
import '../../css/t/tzc2xabqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke4nxkbkt"/><path clip-rule="evenodd" class="sfqi7kbmf"/><path clip-rule="evenodd" class="tzc2xabqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:speaker-bold-duotone" /></template>
