<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh_oxac7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lh_oxac7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:snapcraft" /></template>
