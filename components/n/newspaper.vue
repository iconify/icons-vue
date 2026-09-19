<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9k5qybjm.css';
import '../../css/v/vjhtv-b4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f9k5qybjm"/><path class="vjhtv-b4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:newspaper" /></template>
