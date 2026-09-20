<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhc52fgri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhc52fgri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-left-sharp-fill" /></template>
