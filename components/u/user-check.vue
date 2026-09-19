<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bse37hb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="bse37hb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:user-check" /></template>
