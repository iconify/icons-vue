<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogi60eb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ogi60eb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:planet" /></template>
