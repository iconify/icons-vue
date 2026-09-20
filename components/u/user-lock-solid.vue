<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr2dbacrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rr2dbacrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:user-lock-solid" /></template>
