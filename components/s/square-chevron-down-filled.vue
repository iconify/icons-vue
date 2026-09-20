<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_vo2cbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_vo2cbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-chevron-down-filled" /></template>
