<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjc8iehpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjc8iehpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:parenthesis-right-solid" /></template>
