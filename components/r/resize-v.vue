<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1r1-eb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="s1r1-eb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:resize-v" /></template>
