<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkrznhhan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkrznhhan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:suitcase-alt" /></template>
