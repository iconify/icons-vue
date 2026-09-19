<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3pg_fb6f.css';
import '../../css/z/zunt0gbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="r3pg_fb6f"/><path class="zunt0gbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:transgender-outline" /></template>
