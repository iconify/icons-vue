<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbc_a30nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbc_a30nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:umbrella-fill" /></template>
