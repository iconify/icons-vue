<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eozc8fbep.css';
import '../../css/l/lsxdb1s3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eozc8fbep"/><path class="lsxdb1s3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:reference-existing-ltr" /></template>
