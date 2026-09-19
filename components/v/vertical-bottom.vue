<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd2lkdd-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd2lkdd-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:vertical-bottom" /></template>
