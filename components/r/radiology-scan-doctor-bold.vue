<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmh4fhb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmh4fhb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:radiology-scan-doctor-bold" /></template>
