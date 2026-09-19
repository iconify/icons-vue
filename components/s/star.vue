<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6cgcp9gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="b6cgcp9gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:star" /></template>
