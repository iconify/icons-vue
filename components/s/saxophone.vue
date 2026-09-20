<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt13r4bix.css';
import '../../css/g/gw7mb_bdb.css';
import '../../css/b/bnkx5bbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="lt13r4bix"/><path class="gw7mb_bdb"/><path class="bnkx5bbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:saxophone" /></template>
