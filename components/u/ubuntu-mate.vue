<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atg1-5blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atg1-5blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ubuntu-mate" /></template>
