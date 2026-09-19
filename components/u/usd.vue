<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1fidrk0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="b1fidrk0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:usd" /></template>
