<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm4bc-bnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm4bc-bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:shield" /></template>
