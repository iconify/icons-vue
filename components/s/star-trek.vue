<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myx4-abjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myx4-abjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:star-trek" /></template>
