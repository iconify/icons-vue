<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc6yksbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="uc6yksbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:scale" /></template>
