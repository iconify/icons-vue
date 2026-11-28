<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb2gq0qto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb2gq0qto primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shield-duotone" /></template>
