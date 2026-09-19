<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm5trfjdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="qm5trfjdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:star-slash" /></template>
