<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/feabg3bhd.css';
import '../../css/x/x4gpywx5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="feabg3bhd"/><path class="x4gpywx5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:trash-square-fill" /></template>
