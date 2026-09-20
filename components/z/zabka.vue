<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twacq_bnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twacq_bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:zabka" /></template>
