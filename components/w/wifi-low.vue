<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7_rhsbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7_rhsbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:wifi-low" /></template>
