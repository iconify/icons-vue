<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b12a-lbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="b12a-lbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:roadblock-11" /></template>
