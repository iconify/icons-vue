<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owp3_7g1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="owp3_7g1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:question-circle-solid" /></template>
