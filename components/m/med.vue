<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lftxn_y7p.css';
import '../../css/c/ct7mdezdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lftxn_y7p"/><path class="ct7mdezdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:med" /></template>
