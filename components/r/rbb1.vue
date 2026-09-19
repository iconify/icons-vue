<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6n32bbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6n32bbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:rbb1" /></template>
