<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6kj947-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b6kj947-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:plus-round" /></template>
