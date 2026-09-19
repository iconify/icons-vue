<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzck_dcet.css';
import '../../css/h/hxm77oqrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="xzck_dcet"/><path class="hxm77oqrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:reference-architecture" /></template>
