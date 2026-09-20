<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_tld4ojc.css';
import '../../css/b/bu-7bcciv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b_tld4ojc"/><path class="bu-7bcciv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:todoist" /></template>
