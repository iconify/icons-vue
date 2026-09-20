<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6syj0blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w6syj0blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:social-spotify" /></template>
