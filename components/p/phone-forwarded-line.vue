<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwef98_no.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwef98_no"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:phone-forwarded-line" /></template>
