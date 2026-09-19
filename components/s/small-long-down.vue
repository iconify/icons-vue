<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_f7byxch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_f7byxch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:small-long-down" /></template>
