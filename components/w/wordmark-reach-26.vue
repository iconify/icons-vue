<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyqkh4byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":61,"height":26};
const content = `<path class="kyqkh4byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wordmark-reach-26" /></template>
