<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8zp29bao.css';
import '../../css/d/dfctlpbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8zp29bao"/><path class="dfctlpbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:mask" /></template>
