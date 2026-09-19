<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr0u-obfa.css';
import '../../css/q/qoypj_b7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="mr0u-obfa"/><path class="qoypj_b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:text" /></template>
