<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmov_dv6f.css';
import '../../css/x/xzk6xmbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kmov_dv6f"/><path class="xzk6xmbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:repeat-one" /></template>
