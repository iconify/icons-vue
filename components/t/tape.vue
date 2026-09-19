<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr44fb1gq.css';
import '../../css/n/n9mo1oxei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tr44fb1gq"/><path class="n9mo1oxei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tape" /></template>
