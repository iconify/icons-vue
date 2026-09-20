<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bscp3lbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bscp3lbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:shield-health-safety-line" /></template>
