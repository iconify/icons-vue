<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftpp8ccpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftpp8ccpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:question-circle" /></template>
