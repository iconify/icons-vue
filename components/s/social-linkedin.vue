<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bviy_rbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bviy_rbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-linkedin" /></template>
