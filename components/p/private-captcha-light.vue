<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-vu-m6pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f-vu-m6pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:private-captcha-light" /></template>
