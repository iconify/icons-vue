<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj_ujb63u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj_ujb63u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:radar" /></template>
