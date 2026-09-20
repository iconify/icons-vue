<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhpbq_pxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhpbq_pxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:optuna" /></template>
