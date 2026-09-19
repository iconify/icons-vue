<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_ck-kb7o.css';
import '../../css/k/kyehcvbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f_ck-kb7o"/><path class="kyehcvbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:virtual-private-cloud-alt" /></template>
