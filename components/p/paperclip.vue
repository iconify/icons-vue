<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at0wybcon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="at0wybcon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:paperclip" /></template>
