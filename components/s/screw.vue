<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5ua7wpql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5ua7wpql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:screw" /></template>
