<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bryx4egmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bryx4egmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:refund-back-light" /></template>
