<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnlowcojv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wnlowcojv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:probot" /></template>
