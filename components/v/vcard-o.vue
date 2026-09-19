<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1h895bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1536};
const content = `<path class="b1h895bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:vcard-o" /></template>
