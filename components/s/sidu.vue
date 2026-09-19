<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj-dsql_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="wj-dsql_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:sidu" /></template>
