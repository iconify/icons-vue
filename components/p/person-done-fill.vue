<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvc5-zbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvc5-zbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:person-done-fill" /></template>
