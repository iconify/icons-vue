<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf-hwtb-u.css';
import '../../css/z/z39rqtbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf-hwtb-u"/><path class="z39rqtbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:search-circle-alternate-bold" /></template>
