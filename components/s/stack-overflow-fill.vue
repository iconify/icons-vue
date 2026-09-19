<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti0_56jad.css';
import '../../css/c/c34z_sbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti0_56jad"/><path class="c34z_sbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:stack-overflow-fill" /></template>
