<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_07bhb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":210,"height":700};
const content = `<path class="o_07bhb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:small-arrow-right" /></template>
