<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbd1pyb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbd1pyb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sonarqube" /></template>
