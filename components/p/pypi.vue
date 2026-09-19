<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1aqaybva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b1aqaybva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:pypi" /></template>
