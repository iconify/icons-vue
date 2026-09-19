<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_4qsubgk.css';
import '../../css/o/omqgt0bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_4qsubgk"/><path class="omqgt0bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:phone-call" /></template>
