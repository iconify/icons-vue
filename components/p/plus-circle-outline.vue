<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sih672bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sih672bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:plus-circle-outline" /></template>
