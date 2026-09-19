<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt1yw8cpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zt1yw8cpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:wing" /></template>
