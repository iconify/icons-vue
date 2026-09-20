<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_xwhobze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="b_xwhobze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:wetland-11" /></template>
