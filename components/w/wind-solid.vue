<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h917rt1ow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h917rt1ow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:wind-solid" /></template>
