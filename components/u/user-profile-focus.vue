<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj_f4vbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="fj_f4vbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:user-profile-focus" /></template>
