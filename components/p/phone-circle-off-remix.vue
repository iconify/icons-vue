<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imvv0wbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="imvv0wbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:phone-circle-off-remix" /></template>
