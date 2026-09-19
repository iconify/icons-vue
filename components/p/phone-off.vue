<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruhl7hcfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruhl7hcfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:phone-off" /></template>
