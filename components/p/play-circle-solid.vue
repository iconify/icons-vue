<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef4d2rb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef4d2rb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:play-circle-solid" /></template>
