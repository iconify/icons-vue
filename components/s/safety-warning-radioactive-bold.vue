<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbqi1ub-j.css';
import '../../css/b/bfj6lrbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbqi1ub-j"/><path class="bfj6lrbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:safety-warning-radioactive-bold" /></template>
