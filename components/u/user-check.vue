<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxc_0cc_z.css';
import '../../css/c/c47zhrbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zxc_0cc_z"/><path class="c47zhrbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:user-check" /></template>
