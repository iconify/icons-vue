<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti1-61bnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti1-61bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:toggle-off" /></template>
