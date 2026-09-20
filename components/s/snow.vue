<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zofquwouv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="zofquwouv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:snow" /></template>
