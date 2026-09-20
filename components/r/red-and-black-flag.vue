<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p61-0ivql.css';
import '../../css/x/x5e_3_moj.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="p61-0ivql"/><path class="x5e_3_moj"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:red-and-black-flag" /></template>
