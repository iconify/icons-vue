<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/diraqp4hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="diraqp4hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:noodle-bowl-with-steam" /></template>
