<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm8s9bcod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm8s9bcod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:radiation-off" /></template>
