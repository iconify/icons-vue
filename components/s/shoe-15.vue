<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd11hok7e.css';
import '../../css/r/rw7vibdxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dd11hok7e"/><path class="rw7vibdxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:shoe-15" /></template>
