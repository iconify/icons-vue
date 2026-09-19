<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy2qybcvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sy2qybcvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:stagel-light-2" /></template>
