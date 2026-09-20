<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-n99mbgf.css';
import '../../css/a/atk21rbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f-n99mbgf"/><ellipse class="atk21rbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:printer" /></template>
