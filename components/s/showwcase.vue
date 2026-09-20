<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klf049c-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="klf049c-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:showwcase" /></template>
