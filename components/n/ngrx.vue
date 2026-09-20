<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/youzr_tms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="youzr_tms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ngrx" /></template>
