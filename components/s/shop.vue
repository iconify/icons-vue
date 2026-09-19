<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smq69y8wv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="smq69y8wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:shop" /></template>
