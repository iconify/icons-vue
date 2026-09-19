<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_d8j4ckm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a_d8j4ckm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sms" /></template>
