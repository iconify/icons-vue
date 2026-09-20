<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyystr3mw.css';
import '../../css/k/ko29mcbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hyystr3mw"/><path clip-rule="evenodd" class="ko29mcbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:otp-solid" /></template>
