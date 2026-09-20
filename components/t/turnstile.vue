<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhplffbdf.css';
import '../../css/z/zv-6rgbbp.css';
import '../../css/p/pfmh85w5h.css';
import '../../css/s/sxrpgcc4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zhplffbdf"/><path class="zv-6rgbbp"/><path class="pfmh85w5h"/><path class="sxrpgcc4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:turnstile" /></template>
