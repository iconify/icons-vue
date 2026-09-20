<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrr7lsb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hrr7lsb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:temperature-filled" /></template>
