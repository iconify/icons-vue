<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm5rvjqyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bm5rvjqyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:piano-24" /></template>
