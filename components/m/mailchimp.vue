<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8u7_hugl.css';
import '../../css/e/e9di-eb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8u7_hugl"/><path class="e9di-eb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:mailchimp" /></template>
