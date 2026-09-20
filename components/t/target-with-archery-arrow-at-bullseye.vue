<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm2rlcwdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jm2rlcwdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:target-with-archery-arrow-at-bullseye" /></template>
