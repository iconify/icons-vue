<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn_w55smn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="fn_w55smn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:person-badge-plus-fill" /></template>
