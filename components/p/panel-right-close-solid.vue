<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iosqv_6xw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iosqv_6xw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:panel-right-close-solid" /></template>
