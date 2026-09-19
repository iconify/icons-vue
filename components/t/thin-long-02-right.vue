<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shdnt_bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shdnt_bjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:thin-long-02-right" /></template>
