<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/feeids0fq.css';
import '../../css/w/whujt0lbg.css';
import '../../css/s/sjk5febne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="feeids0fq"/><path class="whujt0lbg"/><path class="sjk5febne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:repeat-48-bold" /></template>
