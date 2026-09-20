<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5wnyc_ou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="d5wnyc_ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:shield-tick-solid" /></template>
