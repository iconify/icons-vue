<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rflrhl7ej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rflrhl7ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:reolink-go" /></template>
