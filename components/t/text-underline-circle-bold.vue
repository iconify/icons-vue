<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob_fhebgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ob_fhebgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-underline-circle-bold" /></template>
