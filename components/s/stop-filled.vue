<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g892u-omi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g892u-omi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:stop-filled" /></template>
