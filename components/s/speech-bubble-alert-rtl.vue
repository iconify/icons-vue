<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-e8ugb3c.css';
import '../../css/d/d-svt8bha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a-e8ugb3c"/><path class="d-svt8bha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:speech-bubble-alert-rtl" /></template>
