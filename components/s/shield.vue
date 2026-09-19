<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah9l-qm1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah9l-qm1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:shield" /></template>
