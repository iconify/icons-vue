<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyr2jybbi.css';
import '../../css/c/cu-wwpbhr.css';
import '../../css/k/ky8qmjbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cyr2jybbi"/><path class="cu-wwpbhr"/><path class="ky8qmjbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:squaredsos" /></template>
