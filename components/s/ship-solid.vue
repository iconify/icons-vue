<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz31dcpqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mz31dcpqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:ship-solid" /></template>
