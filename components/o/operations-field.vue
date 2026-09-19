<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sykatxd1a.css';
import '../../css/l/lmkh-etqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sykatxd1a"/><path class="lmkh-etqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:operations-field" /></template>
