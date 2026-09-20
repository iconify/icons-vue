<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5muktbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="b5muktbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:spa" /></template>
