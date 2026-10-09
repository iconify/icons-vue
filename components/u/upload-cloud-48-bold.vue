<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk_olrbkj.css';
import '../../css/w/wkqj1nbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sk_olrbkj"/><path class="wkqj1nbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:upload-cloud-48-bold" /></template>
