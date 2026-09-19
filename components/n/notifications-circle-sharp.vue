<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygvvp4myp.css';
import '../../css/a/a__8s7rjg.css';
import '../../css/v/v0ghp0p0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ygvvp4myp"/><path class="a__8s7rjg"/><path class="v0ghp0p0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:notifications-circle-sharp" /></template>
