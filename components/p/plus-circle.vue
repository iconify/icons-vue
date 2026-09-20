<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an6b-5b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="an6b-5b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:plus-circle" /></template>
