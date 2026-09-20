<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7jj56biu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="d7jj56biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:village-11" /></template>
