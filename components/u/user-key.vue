<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1__oqeqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1__oqeqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user-key" /></template>
