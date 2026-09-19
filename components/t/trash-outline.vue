<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gowarsb4c.css';
import '../../css/b/b0c14i84a.css';
import '../../css/f/fyztchb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gowarsb4c"/><path class="b0c14i84a"/><path class="fyztchb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:trash-outline" /></template>
