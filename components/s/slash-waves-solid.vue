<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmk8c0bnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmk8c0bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:slash-waves-solid" /></template>
