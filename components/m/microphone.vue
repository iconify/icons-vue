<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h62f4pbkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h62f4pbkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:microphone" /></template>
