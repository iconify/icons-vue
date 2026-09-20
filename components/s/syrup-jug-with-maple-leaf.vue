<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk2q3ab5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lk2q3ab5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:syrup-jug-with-maple-leaf" /></template>
