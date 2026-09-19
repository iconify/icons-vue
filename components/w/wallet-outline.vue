<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aufc9acsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aufc9acsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:wallet-outline" /></template>
