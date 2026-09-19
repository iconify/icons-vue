<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igo_o-d5w.css';
import '../../css/d/dnmne6b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="igo_o-d5w"/><path class="dnmne6b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:time" /></template>
