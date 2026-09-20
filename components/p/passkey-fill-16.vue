<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra00e7bqq.css';
import '../../css/x/xk-_fybgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ra00e7bqq"/><path class="xk-_fybgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:passkey-fill-16" /></template>
