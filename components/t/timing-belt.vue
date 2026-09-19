<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3lbonbua.css';
import '../../css/b/bq5th6b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="g3lbonbua"/><path class="bq5th6b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:timing-belt" /></template>
