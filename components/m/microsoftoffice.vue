<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hos4-7jae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hos4-7jae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:microsoftoffice" /></template>
