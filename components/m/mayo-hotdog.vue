<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a82xcdcpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":512};
const content = `<path class="a82xcdcpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:mayo-hotdog" /></template>
