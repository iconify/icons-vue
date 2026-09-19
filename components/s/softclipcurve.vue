<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1pm3vbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="b1pm3vbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:softclipcurve" /></template>
