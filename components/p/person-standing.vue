<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5u_v5hac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5u_v5hac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:person-standing" /></template>
