<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur8-5xb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur8-5xb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pendant-cher" /></template>
