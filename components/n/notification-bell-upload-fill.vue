<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd-49accd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jd-49accd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:notification-bell-upload-fill" /></template>
