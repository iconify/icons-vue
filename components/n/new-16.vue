<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kic12wbzz.css';
import '../../css/h/hm17yp49j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kic12wbzz"/><path clip-rule="evenodd" class="hm17yp49j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:new-16" /></template>
