<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti26dd_bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti26dd_bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:notification-bell-snooze-2-fill" /></template>
