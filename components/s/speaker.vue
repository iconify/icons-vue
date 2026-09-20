<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw4887bwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tw4887bwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:speaker" /></template>
