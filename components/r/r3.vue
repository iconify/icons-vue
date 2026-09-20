<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v46z5iboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v46z5iboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:r3" /></template>
