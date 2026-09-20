<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h13zd3bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h13zd3bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:quote-left" /></template>
