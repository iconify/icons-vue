<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b__i1vbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="b__i1vbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:nas" /></template>
