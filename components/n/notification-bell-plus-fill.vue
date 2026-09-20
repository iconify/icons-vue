<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig5m35nvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig5m35nvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:notification-bell-plus-fill" /></template>
