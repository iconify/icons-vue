<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w33oqo5oh.css';
import '../../css/c/cjcvn3b5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="w33oqo5oh"/><path class="cjcvn3b5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:rancher-wordmark" /></template>
