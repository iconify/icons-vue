<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j20z8obis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j20z8obis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:unmute" /></template>
