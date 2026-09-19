<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf1fo6loa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qf1fo6loa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:plus-square" /></template>
