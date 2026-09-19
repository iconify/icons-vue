<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygy8b74rs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ygy8b74rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:timer-sharp" /></template>
