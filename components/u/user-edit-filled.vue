<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfeutzb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfeutzb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-edit-filled" /></template>
