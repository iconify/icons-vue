<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqsbbac6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iqsbbac6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:material-design" /></template>
