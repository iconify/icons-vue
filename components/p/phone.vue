<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb9xe1bqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-6,"top":-2};
const content = `<path class="gb9xe1bqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:phone" /></template>
