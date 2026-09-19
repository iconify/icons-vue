<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaw774b1y.css';
import '../../css/b/bjy9zyb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="aaw774b1y"/><path class="bjy9zyb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:selenium" /></template>
