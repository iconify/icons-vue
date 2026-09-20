<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skniqjfmb.css';
import '../../css/d/d6q6fgbmj.css';
import '../../css/t/ts3x6_b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1100,"height":1100};
const content = `<path class="skniqjfmb"/><path class="d6q6fgbmj"/><path class="ts3x6_b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:openbao" /></template>
