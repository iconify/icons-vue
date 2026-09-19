<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exjxxsb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exjxxsb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:service-instance-outlined" /></template>
