<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsgd_fb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":684,"height":1568};
const content = `<path class="zsgd_fb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ralph-lauren-dark" /></template>
