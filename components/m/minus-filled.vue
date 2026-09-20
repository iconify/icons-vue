<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tygc8dbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tygc8dbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:minus-filled" /></template>
