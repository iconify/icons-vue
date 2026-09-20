<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgbx9bfba.css';
import '../../css/l/l1tfhcbvb.css';
import '../../css/f/f6kx-ccba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgbx9bfba"/><path class="l1tfhcbvb"/><path class="f6kx-ccba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:you" /></template>
