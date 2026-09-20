<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9a0qsblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9a0qsblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:tallymark-3" /></template>
