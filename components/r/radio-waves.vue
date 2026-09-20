<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut3_chb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ut3_chb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:radio-waves" /></template>
