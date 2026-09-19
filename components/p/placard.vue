<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja9mf_b0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ja9mf_b0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:placard" /></template>
