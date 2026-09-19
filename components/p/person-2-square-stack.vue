<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw_5fmbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="qw_5fmbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:person-2-square-stack" /></template>
