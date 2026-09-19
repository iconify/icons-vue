<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcfai4b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcfai4b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:zucchini" /></template>
