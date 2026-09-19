<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtqm8qbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="qtqm8qbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:textformat-abc" /></template>
