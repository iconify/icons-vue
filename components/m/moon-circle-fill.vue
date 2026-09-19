<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0_g8l7oa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="s0_g8l7oa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:moon-circle-fill" /></template>
