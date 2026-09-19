<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crhc3cbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crhc3cbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shield-quarter" /></template>
