<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwus2bcyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwus2bcyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:number-8-box-multiple-outline" /></template>
