<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jor-usn7v.css';
import '../../css/i/iqccs38dr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jor-usn7v"/><path class="iqccs38dr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:minus-square" /></template>
