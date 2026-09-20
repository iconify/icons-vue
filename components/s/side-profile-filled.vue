<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehsqweevr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ehsqweevr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:side-profile-filled" /></template>
