<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apshrob0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apshrob0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:user-plus-solid" /></template>
