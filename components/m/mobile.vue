<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0lnft6tj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0lnft6tj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:mobile" /></template>
