<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t13a7cmwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t13a7cmwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:tire" /></template>
