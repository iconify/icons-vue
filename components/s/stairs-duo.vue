<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9dszyztl.css';
import '../../css/b/bxx_4tbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9dszyztl secondary"/><path class="bxx_4tbiq primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:stairs-duo" /></template>
