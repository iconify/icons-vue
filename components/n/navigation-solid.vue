<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-6zgrbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-6zgrbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:navigation-solid" /></template>
