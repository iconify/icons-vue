<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2yhjhbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="l2yhjhbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:retweet" /></template>
