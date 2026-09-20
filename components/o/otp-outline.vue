<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wet0bllvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wet0bllvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:otp-outline" /></template>
