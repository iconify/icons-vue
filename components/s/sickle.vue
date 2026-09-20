<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhv2rb_dl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhv2rb_dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sickle" /></template>
