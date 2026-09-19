<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlfb33qbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":33,"height":26};
const content = `<path class="rlfb33qbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wordmark-sell-26" /></template>
