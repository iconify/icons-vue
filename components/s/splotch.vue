<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gowdz_mtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gowdz_mtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:splotch" /></template>
