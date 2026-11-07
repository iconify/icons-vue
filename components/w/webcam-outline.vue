<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tnf6ldb9q.css';
import '../../css/z/zjftgfb_b.css';
import '../../css/c/c32p5b3tz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tnf6ldb9q"/><path class="zjftgfb_b"/><path clip-rule="evenodd" class="c32p5b3tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:webcam-outline" /></template>
