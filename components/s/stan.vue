<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isbvslb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="isbvslb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:stan" /></template>
