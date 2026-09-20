<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy3dp1yll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy3dp1yll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:shield-security-line" /></template>
