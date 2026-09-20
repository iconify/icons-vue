<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko8qmo0ue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko8qmo0ue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:sync" /></template>
