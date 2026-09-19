<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubtji8yyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubtji8yyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ue-epicboom" /></template>
