<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqxpd_v_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="jqxpd_v_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:text-insert" /></template>
