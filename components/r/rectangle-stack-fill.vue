<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp1vvgsyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="sp1vvgsyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rectangle-stack-fill" /></template>
