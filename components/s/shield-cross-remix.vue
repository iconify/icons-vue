<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awu035ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="awu035ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:shield-cross-remix" /></template>
