<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-d_8ghxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="x-d_8ghxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:person-alt-circle-fill" /></template>
