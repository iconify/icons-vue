<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1rmvbc_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1rmvbc_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tennis-ball-alt" /></template>
