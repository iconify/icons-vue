<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dktkprebk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dktkprebk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:map-pin-snooze-inside-solid" /></template>
