<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1_2t6b9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1_2t6b9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:minus-octagon-solid" /></template>
