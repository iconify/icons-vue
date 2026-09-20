<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwvuisbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwvuisbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:south-west-line" /></template>
