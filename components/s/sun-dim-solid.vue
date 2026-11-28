<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zac9grbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zac9grbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sun-dim-solid" /></template>
