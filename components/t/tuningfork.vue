<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qng5m212p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="qng5m212p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:tuningfork" /></template>
