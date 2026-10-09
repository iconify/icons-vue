<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxmhc0blm.css';
import '../../css/e/eirizwgnj.css';
import '../../css/q/qck7pccit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uxmhc0blm"/><path class="eirizwgnj"/><path class="qck7pccit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sort-alpha-20" /></template>
