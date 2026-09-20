<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/libkqqbsb.css';
import '../../css/u/u44crn52a.css';
import '../../css/a/af5m2ccgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="libkqqbsb"/><path clip-rule="evenodd" class="u44crn52a"/><path class="af5m2ccgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:rss-solid" /></template>
