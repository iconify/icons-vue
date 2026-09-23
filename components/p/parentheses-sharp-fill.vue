<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epm1c_bnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epm1c_bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:parentheses-sharp-fill" /></template>
