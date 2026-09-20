<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu0jo_bhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu0jo_bhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:maze" /></template>
