<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2r0fbbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":709};
const content = `<path class="r2r0fbbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:wrench" /></template>
