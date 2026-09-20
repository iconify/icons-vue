<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tl9f0ocwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl9f0ocwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:octagon-minus-2" /></template>
