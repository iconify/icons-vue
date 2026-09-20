<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq532vbvh.css';
import '../../css/r/r-nejf7ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq532vbvh"/><path class="r-nejf7ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:trophy-light" /></template>
