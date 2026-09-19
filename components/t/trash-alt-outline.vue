<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmhl_gbis.css';
import '../../css/s/ssrw9lb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmhl_gbis"/><path clip-rule="evenodd" class="ssrw9lb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:trash-alt-outline" /></template>
