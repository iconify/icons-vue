<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja05_tojk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ja05_tojk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:moment-timezone" /></template>
