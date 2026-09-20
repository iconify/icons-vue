<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn2zd0bek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn2zd0bek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:widget5-filled" /></template>
