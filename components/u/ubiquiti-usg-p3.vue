<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed4k_eb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ed4k_eb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ubiquiti-usg-p3" /></template>
