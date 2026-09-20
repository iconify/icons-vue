<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6ii2cbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k6ii2cbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:suitcase2" /></template>
