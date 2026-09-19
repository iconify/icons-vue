<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o804cb_ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o804cb_ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:transmission-virus-increase-rate" /></template>
