<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw1ug-btp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bw1ug-btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:pin-16" /></template>
