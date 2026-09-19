<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le5_uo-aa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":960};
const content = `<path class="le5_uo-aa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:playvideo" /></template>
