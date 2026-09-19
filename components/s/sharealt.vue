<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvrzfbc7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bvrzfbc7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:sharealt" /></template>
