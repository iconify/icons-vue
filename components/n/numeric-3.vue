<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu-nt_zvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu-nt_zvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-3" /></template>
