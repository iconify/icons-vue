<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebi4uebqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebi4uebqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:right-indent-alt" /></template>
