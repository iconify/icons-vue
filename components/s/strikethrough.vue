<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpiua4svc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpiua4svc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:strikethrough" /></template>
